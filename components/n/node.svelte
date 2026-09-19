<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu1rz2bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu1rz2bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:node" {...props}></Icon>

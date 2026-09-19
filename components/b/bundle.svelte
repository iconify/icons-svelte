<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksizhkscx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksizhkscx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:bundle" {...props}></Icon>

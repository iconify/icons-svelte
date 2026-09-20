<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzpzurt2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzpzurt2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rootsbedrock" {...props}></Icon>

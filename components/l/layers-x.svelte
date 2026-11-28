<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eefz75dzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eefz75dzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:layers-x" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2x6lxjuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2x6lxjuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:milestone" {...props}></Icon>

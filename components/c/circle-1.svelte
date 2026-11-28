<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsrbwcckl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsrbwcckl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:circle-1" {...props}></Icon>

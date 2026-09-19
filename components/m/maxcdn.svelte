<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aika05jib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aika05jib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:maxcdn" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gls42abvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gls42abvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bright" {...props}></Icon>

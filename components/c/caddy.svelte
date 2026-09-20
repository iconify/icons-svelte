<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1zmubav.css';
import '../../css/k/kux3ecbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gr1zmubav"/><path class="kux3ecbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:caddy" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecnugpbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ecnugpbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:ice-skating" {...props}></Icon>

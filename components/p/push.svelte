<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3twlpavd.css';
import '../../css/e/eztzo_ccz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k3twlpavd"/><path class="eztzo_ccz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:push" {...props}></Icon>

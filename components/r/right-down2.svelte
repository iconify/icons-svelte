<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azscm5t4y.css';
import '../../css/q/qqfentbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="azscm5t4y"/><path class="qqfentbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:right-down2" {...props}></Icon>

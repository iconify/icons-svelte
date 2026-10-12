<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efpda2bqy.css';
import '../../css/m/mme4osblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="efpda2bqy"/><path class="mme4osblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-list-stroke-20" {...props}></Icon>

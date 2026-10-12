<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcerxm02m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kcerxm02m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:paper-plane-stroke-20" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eba7bgh4x.css';
import '../../css/k/k-8fhdbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eba7bgh4x"/><path class="k-8fhdbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-rtl-20" {...props}></Icon>

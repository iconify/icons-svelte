<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k26amtbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k26amtbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:menu" {...props}></Icon>

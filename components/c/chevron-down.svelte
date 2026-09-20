<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyepbk-hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="uyepbk-hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-down" {...props}></Icon>

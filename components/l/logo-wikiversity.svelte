<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed_jr85kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ed_jr85kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikiversity" {...props}></Icon>

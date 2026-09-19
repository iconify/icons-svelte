<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adme_kbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="adme_kbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:pinterest-p" {...props}></Icon>

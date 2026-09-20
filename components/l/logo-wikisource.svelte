<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojls-ccqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ojls-ccqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikisource" {...props}></Icon>

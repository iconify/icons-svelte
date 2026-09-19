<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wafu_qb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wafu_qb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth-europe-africa" {...props}></Icon>

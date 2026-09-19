<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqdqqi13i.css';
import '../../css/a/a3y0hhb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eqdqqi13i"/><path class="a3y0hhb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-elo-publishing" {...props}></Icon>

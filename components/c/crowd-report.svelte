<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu_6g5b9q.css';
import '../../css/n/nu2_-nbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zu_6g5b9q"/><path class="nu2_-nbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:crowd-report" {...props}></Icon>

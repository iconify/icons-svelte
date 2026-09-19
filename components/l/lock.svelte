<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk_ksfbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":840};
const content = `<path class="bk_ksfbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:lock" {...props}></Icon>

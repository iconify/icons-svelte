<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg_kcdcxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qg_kcdcxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:journal-whills" {...props}></Icon>

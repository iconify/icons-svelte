<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgrj_wbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fgrj_wbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:badge-plus-radiowaves-right" {...props}></Icon>

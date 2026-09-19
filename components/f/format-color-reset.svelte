<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smmymf_ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":392};
const content = `<path class="smmymf_ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-color-reset" {...props}></Icon>

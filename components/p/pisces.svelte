<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aea866bch.css';
import '../../css/v/vbj9b3b9v.css';
import '../../css/k/kmkesyb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aea866bch"/><path class="vbj9b3b9v"/><path class="kmkesyb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pisces" {...props}></Icon>

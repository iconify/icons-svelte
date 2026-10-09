<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/x/xz_cw0bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="xz_cw0bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clock-1-20-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzpmrsbbt.css';
import '../../css/y/yg_pakoyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzpmrsbbt"/><path class="yg_pakoyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-octocat" {...props}></Icon>

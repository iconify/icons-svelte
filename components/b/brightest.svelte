<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsce67bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nsce67bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:brightest" {...props}></Icon>

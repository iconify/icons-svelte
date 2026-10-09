<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti48nsbex.css';
import '../../css/a/ar3qzv4of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti48nsbex"/><path class="ar3qzv4of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hvdc-converter-20" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqb284kyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="hqb284kyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:flag" {...props}></Icon>

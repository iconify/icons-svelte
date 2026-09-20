<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oatd-7bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oatd-7bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:poo-solid" {...props}></Icon>

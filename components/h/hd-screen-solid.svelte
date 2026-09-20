<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib7ibmduz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ib7ibmduz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hd-screen-solid" {...props}></Icon>

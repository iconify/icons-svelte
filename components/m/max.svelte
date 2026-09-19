<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk6oirbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hk6oirbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:max" {...props}></Icon>

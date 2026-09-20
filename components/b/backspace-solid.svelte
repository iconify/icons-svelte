<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6jmubclb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t6jmubclb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:backspace-solid" {...props}></Icon>

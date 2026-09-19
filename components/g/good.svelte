<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqb0x2bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":679};
const content = `<path class="sqb0x2bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:good" {...props}></Icon>

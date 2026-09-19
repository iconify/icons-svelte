<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8l66bc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c8l66bc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:box-subtract-solid" {...props}></Icon>

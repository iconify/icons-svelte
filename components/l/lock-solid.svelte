<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwe7utqcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wwe7utqcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:lock-solid" {...props}></Icon>

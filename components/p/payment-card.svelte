<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzjxf3r3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uzjxf3r3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:payment-card" {...props}></Icon>

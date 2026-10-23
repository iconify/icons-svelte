<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5od71bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5od71bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:quantum-computer" {...props}></Icon>

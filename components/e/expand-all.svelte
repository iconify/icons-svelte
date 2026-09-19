<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyl2igb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gyl2igb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:expand-all" {...props}></Icon>

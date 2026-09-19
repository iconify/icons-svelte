<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pne0v33if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pne0v33if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:font-color-swatch" {...props}></Icon>

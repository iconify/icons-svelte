<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyg5myhoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tyg5myhoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:diamond-solid" {...props}></Icon>

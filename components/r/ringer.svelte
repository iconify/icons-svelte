<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzpvu9bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jzpvu9bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ringer" {...props}></Icon>

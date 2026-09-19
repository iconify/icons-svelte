<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bez4ssb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bez4ssb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:generate" {...props}></Icon>

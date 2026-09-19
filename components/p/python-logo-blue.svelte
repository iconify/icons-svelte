<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-y3f3b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x-y3f3b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:python-logo-blue" {...props}></Icon>

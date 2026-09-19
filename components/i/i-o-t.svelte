<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iar3svb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iar3svb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:i-o-t" {...props}></Icon>

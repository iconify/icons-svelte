<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fin5uxb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fin5uxb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cloudversify" {...props}></Icon>

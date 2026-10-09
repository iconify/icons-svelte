<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4pa64bjg.css';
import '../../css/b/banax9p2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i4pa64bjg"/><path class="banax9p2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bread-20" {...props}></Icon>

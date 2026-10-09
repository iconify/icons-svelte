<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5zkycj1r.css';
import '../../css/u/uwnsfhbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j5zkycj1r"/><path class="uwnsfhbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cast-48" {...props}></Icon>

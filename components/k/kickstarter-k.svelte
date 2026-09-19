<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0owzbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lc0owzbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:kickstarter-k" {...props}></Icon>

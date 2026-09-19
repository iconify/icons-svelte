<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc2bejsmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rc2bejsmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:internet-archive" {...props}></Icon>

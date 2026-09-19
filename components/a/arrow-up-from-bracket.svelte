<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtsx69eye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wtsx69eye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-up-from-bracket" {...props}></Icon>

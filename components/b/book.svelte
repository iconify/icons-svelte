<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e98uzib3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":614};
const content = `<path class="e98uzib3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:book" {...props}></Icon>

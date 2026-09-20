<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-cyjnb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="e-cyjnb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-snow" {...props}></Icon>

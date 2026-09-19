<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-u4xnbot.css';
import '../../css/b/b1gskgvdy.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-u4xnbot"/><path class="b1gskgvdy"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accessibility-color" {...props}></Icon>

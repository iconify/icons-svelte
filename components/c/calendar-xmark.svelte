<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2ly39s3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n2ly39s3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:calendar-xmark" {...props}></Icon>

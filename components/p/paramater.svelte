<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7-z29e1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":640};
const content = `<path class="a7-z29e1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:paramater" {...props}></Icon>

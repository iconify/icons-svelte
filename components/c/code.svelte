<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol5jczc6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":614};
const content = `<path class="ol5jczc6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:code" {...props}></Icon>

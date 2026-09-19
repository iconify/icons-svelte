<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb2ic2ncu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="gb2ic2ncu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:copyapp" {...props}></Icon>

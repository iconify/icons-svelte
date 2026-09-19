<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta22xjbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":718,"height":690};
const content = `<path class="ta22xjbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:amazon" {...props}></Icon>

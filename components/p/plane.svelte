<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfdaihttu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="zfdaihttu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:plane" {...props}></Icon>

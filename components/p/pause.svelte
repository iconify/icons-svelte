<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqci6gbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zqci6gbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pause" {...props}></Icon>

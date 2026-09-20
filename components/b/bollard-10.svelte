<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1qxmdatg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="g1qxmdatg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:bollard-10" {...props}></Icon>

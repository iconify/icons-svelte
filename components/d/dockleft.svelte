<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsgfetbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zsgfetbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:dockleft" {...props}></Icon>

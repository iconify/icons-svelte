<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haxltpbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="haxltpbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-slack" {...props}></Icon>

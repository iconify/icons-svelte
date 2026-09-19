<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ackp62swz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ackp62swz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:home-verify" {...props}></Icon>

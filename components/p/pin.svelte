<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyt7w2bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tyt7w2bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pin" {...props}></Icon>

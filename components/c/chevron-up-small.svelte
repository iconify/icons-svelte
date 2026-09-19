<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiup1veat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eiup1veat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-up-small" {...props}></Icon>

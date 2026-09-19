<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iavtan26b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iavtan26b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:align-vertical-center" {...props}></Icon>

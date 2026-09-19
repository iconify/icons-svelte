<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6-rcjbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y6-rcjbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:installation" {...props}></Icon>

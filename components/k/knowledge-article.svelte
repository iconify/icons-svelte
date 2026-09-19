<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlegls60l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wlegls60l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:knowledge-article" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhhe-8bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bhhe-8bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:color" {...props}></Icon>

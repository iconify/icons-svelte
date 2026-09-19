<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2to0hbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n2to0hbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:document-reply" {...props}></Icon>

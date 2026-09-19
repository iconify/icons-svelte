<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4291thww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e4291thww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pinned-fill" {...props}></Icon>

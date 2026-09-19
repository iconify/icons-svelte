<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx8vx6qnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cx8vx6qnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-chevron-left" {...props}></Icon>

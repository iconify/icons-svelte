<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqu7-60id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="aqu7-60id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:backlog-list" {...props}></Icon>

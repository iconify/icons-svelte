<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo65a95px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bo65a95px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:agriculture-analytics" {...props}></Icon>

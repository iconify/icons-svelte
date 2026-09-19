<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1-koubcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="g1-koubcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:plogger" {...props}></Icon>

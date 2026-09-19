<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-p7vfblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="q-p7vfblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:calendar" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q61yqbc-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q61yqbc-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:grin-squint-tears" {...props}></Icon>

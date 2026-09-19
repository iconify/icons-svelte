<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3tz-4byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f3tz-4byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:instapaper" {...props}></Icon>

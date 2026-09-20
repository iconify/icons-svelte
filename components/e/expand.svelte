<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtvh7v3ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jtvh7v3ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:expand" {...props}></Icon>

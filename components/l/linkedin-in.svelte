<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2r06bb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q2r06bb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:linkedin-in" {...props}></Icon>

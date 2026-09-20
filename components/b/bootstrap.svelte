<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6jc6qbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q6jc6qbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bootstrap" {...props}></Icon>

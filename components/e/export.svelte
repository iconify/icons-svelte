<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcafp3bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jcafp3bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:export" {...props}></Icon>

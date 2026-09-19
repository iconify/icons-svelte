<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbygz4bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jbygz4bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:coupling-facility" {...props}></Icon>

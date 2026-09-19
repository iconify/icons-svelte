<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9jtd3mcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f9jtd3mcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-minus-fill" {...props}></Icon>

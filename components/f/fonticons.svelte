<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9v8zkb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="o9v8zkb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:fonticons" {...props}></Icon>

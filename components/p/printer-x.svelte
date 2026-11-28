<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1rn0t1rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1rn0t1rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:printer-x" {...props}></Icon>

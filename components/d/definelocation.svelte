<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3wo6h44i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="f3wo6h44i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:definelocation" {...props}></Icon>

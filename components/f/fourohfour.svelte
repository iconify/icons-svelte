<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/due149pmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="due149pmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fourohfour" {...props}></Icon>

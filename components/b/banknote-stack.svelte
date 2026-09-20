<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc011j55m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nc011j55m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:banknote-stack" {...props}></Icon>

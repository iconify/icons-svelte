<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3ijj1g6b.css';
import '../../css/y/y8xl5o4fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="n3ijj1g6b"/><path class="y8xl5o4fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:host-line" {...props}></Icon>

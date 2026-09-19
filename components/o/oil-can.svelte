<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/som-8wzkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="som-8wzkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:oil-can" {...props}></Icon>

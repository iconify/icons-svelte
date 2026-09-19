<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn4unmb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nn4unmb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:kiwi-bird" {...props}></Icon>

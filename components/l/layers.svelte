<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf17anogk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hf17anogk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:layers" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8rojwb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q8rojwb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:play2" {...props}></Icon>

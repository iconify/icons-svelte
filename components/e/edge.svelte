<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq1hf1bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nq1hf1bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:edge" {...props}></Icon>

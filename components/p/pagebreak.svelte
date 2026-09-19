<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzlu_i1rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uzlu_i1rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pagebreak" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx2-j8bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jx2-j8bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bold" {...props}></Icon>

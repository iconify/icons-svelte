<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob0fysbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ob0fysbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pentagon" {...props}></Icon>

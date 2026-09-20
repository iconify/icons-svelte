<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neu3zkbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="neu3zkbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-right-circle-outline" {...props}></Icon>

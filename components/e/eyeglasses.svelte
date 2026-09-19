<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcu0wuc1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lcu0wuc1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:eyeglasses" {...props}></Icon>

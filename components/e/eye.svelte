<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k16fydktf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k16fydktf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eye" {...props}></Icon>

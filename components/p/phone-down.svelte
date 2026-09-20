<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhx94wbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mhx94wbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down" {...props}></Icon>

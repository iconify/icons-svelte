<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7sincczq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="t7sincczq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:broom" {...props}></Icon>

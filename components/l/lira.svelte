<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en241i7xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en241i7xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lira" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywzk8rb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywzk8rb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:highlight" {...props}></Icon>

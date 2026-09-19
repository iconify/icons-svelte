<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj59ymb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj59ymb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pin-slash-alt-filled" {...props}></Icon>

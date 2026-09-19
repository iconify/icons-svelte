<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbyhpqj2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbyhpqj2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-minus-filled" {...props}></Icon>

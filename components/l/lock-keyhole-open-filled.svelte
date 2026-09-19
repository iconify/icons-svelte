<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4ybzybmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ybzybmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-keyhole-open-filled" {...props}></Icon>

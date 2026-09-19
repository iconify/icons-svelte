<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j65vee0iz.css';
import '../../css/q/qux_2305e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="j65vee0iz"/><path class="qux_2305e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gaming-filled" {...props}></Icon>

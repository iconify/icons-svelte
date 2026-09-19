<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_o-u7b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="b_o-u7b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:button-filled" {...props}></Icon>

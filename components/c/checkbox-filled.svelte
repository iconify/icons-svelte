<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhsdat93n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="xhsdat93n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:checkbox-filled" {...props}></Icon>

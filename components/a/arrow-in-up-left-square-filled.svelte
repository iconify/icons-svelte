<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc17l7bwn.css';
import '../../css/z/zar1cn4so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc17l7bwn"/><path class="zar1cn4so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-left-square-filled" {...props}></Icon>

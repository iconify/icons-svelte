<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw3py73bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw3py73bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-left-alt-filled" {...props}></Icon>

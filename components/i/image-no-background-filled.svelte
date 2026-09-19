<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ax2rb3c.css';
import '../../css/z/zsbatf1yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ax2rb3c"/><path class="zsbatf1yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-no-background-filled" {...props}></Icon>

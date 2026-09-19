<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu27xjmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvu27xjmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:champagne" {...props}></Icon>

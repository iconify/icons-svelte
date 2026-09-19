<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqq2j3bkt.css';
import '../../css/e/esv5bmbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqq2j3bkt"/><path class="esv5bmbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:coffee-filled" {...props}></Icon>

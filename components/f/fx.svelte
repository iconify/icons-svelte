<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnxp4hbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnxp4hbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:fx" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxwa51bzx.css';
import '../../css/l/l7ztl2cyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxwa51bzx"/><path class="l7ztl2cyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:create" {...props}></Icon>

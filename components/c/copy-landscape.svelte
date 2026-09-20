<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwl8tszbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwl8tszbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:copy-landscape" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk7bhvf1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk7bhvf1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-hangouts" {...props}></Icon>

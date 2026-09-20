<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk_bbsb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk_bbsb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:arm" {...props}></Icon>

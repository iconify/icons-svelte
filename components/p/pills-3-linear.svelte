<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hqpl1bcby.css';
import '../../css/c/cns6ly1bg.css';
import '../../css/p/p1tpmgbyh.css';
import '../../css/h/hqsaabc6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hqpl1bcby"/><path class="cns6ly1bg"/><path class="p1tpmgbyh"/><path class="hqsaabc6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-3-linear" {...props}></Icon>

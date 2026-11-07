<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maw4ikbnh.css';
import '../../css/y/yn4p-lbjx.css';
import '../../css/t/tjhcftl1w.css';
import '../../css/o/osemxebgc.css';
import '../../css/j/jy0yf6bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maw4ikbnh"/><path class="yn4p-lbjx"/><path class="tjhcftl1w"/><path clip-rule="evenodd" class="osemxebgc"/><path class="jy0yf6bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-full-minimalistic-outline" {...props}></Icon>

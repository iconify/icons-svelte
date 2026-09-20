<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnrexiitu.css';
import '../../css/h/hzmc-yyoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnrexiitu"/><path class="hzmc-yyoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:locker-room-suitcase-key-bold" {...props}></Icon>

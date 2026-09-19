<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpm8a6xpl.css';
import '../../css/y/yvc722b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpm8a6xpl"/><path class="yvc722b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dailymotion" {...props}></Icon>

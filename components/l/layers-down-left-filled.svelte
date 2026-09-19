<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsvcw96ah.css';
import '../../css/y/yal5mhbcs.css';
import '../../css/k/kbk3tibjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsvcw96ah"/><path class="yal5mhbcs"/><path class="kbk3tibjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-down-left-filled" {...props}></Icon>

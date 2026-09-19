<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm_qsybka.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/d/dwtkkyb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_qsybka"/><path class="bwibdw4bb"/><path class="dwtkkyb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laugh" {...props}></Icon>

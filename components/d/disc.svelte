<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nllflp_eh.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/d/dosjvkbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nllflp_eh"/><path class="bwibdw4bb"/><path class="dosjvkbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:disc" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxobl-b0u.css';
import '../../css/p/p42897ycd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxobl-b0u"/><path class="p42897ycd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rocket" {...props}></Icon>

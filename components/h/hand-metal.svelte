<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2pzlm6fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2pzlm6fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hand-metal" {...props}></Icon>

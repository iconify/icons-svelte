<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk9yzt_fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk9yzt_fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-neutral-fill-round" {...props}></Icon>

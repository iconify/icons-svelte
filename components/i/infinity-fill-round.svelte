<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rew2wgbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rew2wgbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:infinity-fill-round" {...props}></Icon>

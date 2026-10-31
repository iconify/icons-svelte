<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v03fs2b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v03fs2b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:captions-fill-round" {...props}></Icon>

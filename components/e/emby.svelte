<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5ugx6yak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ugx6yak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:emby" {...props}></Icon>

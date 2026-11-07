<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtwkzehzt.css';
import '../../css/h/hp4q8k9dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtwkzehzt"/><path clip-rule="evenodd" class="hp4q8k9dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:balloon-bold" {...props}></Icon>

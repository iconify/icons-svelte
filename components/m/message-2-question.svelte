<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtgwkv1mf.css';
import '../../css/p/p8m96-3vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtgwkv1mf"/><path clip-rule="evenodd" class="p8m96-3vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:message-2-question" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i53ry7bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i53ry7bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:emo-emotional-filled" {...props}></Icon>

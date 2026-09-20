<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6vnyqb9w.css';
import '../../css/w/wk8vleb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6vnyqb9w"/><path class="wk8vleb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mute" {...props}></Icon>

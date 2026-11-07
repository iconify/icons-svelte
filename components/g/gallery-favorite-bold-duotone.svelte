<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhvzr3pxx.css';
import '../../css/v/vwvsfxegk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhvzr3pxx"/><path clip-rule="evenodd" class="vwvsfxegk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favorite-bold-duotone" {...props}></Icon>

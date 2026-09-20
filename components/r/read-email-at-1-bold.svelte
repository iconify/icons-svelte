<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdmk0nb5w.css';
import '../../css/l/loieh1tve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdmk0nb5w"/><path class="loieh1tve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:read-email-at-1-bold" {...props}></Icon>

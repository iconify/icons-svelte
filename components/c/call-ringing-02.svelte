<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh1xwcb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh1xwcb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-ringing-02" {...props}></Icon>

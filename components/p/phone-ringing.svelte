<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzhz92pui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzhz92pui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-ringing" {...props}></Icon>

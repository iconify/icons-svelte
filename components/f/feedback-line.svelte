<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtki5oofd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtki5oofd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:feedback-line" {...props}></Icon>

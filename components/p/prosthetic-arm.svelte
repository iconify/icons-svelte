<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebxx94pjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebxx94pjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:prosthetic-arm" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii3fyacso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii3fyacso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-4-line" {...props}></Icon>

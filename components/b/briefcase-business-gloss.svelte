<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8y25ccnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8y25ccnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-business-gloss" {...props}></Icon>

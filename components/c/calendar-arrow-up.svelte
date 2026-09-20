<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z36ypqb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z36ypqb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-up" {...props}></Icon>

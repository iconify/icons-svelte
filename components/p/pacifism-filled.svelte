<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soj4qtblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soj4qtblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pacifism-filled" {...props}></Icon>

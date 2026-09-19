<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxn26ubua.css';
import '../../css/i/inhewssvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxn26ubua"/><path class="inhewssvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:buildings" {...props}></Icon>

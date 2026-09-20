<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okwossb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="okwossb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-earpods-airpods-audio-earpods-music-earbuds-true-wireless" {...props}></Icon>

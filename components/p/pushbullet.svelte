<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3u8vmzwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3u8vmzwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pushbullet" {...props}></Icon>

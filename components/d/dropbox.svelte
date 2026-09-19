<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg7d5d_ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="tg7d5d_ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dropbox" {...props}></Icon>

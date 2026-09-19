<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4myf3box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="c4myf3box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:play-list" {...props}></Icon>

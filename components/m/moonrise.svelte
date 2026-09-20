<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h92d--bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="h92d--bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moonrise" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5a8qrbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5a8qrbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:play-gloss" {...props}></Icon>

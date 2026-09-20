<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu-ii1brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu-ii1brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mode-embedding-filled" {...props}></Icon>

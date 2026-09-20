<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi-m-sboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi-m-sboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:edotleclerc" {...props}></Icon>

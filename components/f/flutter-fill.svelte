<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hswb42bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hswb42bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flutter-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kta6hubpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kta6hubpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flutter-line" {...props}></Icon>

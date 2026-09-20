<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vesf7-b_g.css';
import '../../css/h/h_auobb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vesf7-b_g"/><path class="h_auobb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:internet-network-download" {...props}></Icon>

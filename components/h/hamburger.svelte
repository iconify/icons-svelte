<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voqzwt5oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voqzwt5oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hamburger" {...props}></Icon>

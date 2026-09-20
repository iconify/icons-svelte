<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-s9mwn3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-s9mwn3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hexagon-line" {...props}></Icon>

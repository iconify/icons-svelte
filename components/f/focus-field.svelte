<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6e7-tnja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6e7-tnja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:focus-field" {...props}></Icon>

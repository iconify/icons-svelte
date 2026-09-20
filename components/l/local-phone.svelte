<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsjz9qa0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsjz9qa0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-phone" {...props}></Icon>

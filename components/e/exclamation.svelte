<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emxwkimnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emxwkimnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:exclamation" {...props}></Icon>

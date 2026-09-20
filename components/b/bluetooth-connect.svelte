<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6z92pbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6z92pbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bluetooth-connect" {...props}></Icon>

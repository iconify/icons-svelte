<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4eh32wru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4eh32wru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:night-light" {...props}></Icon>

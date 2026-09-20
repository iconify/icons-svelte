<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo5ufz-lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo5ufz-lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:layers" {...props}></Icon>

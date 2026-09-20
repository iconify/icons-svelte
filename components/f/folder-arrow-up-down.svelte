<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vse5ibbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vse5ibbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-up-down" {...props}></Icon>

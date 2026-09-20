<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fytd5lhkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fytd5lhkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blood-alert-outline" {...props}></Icon>

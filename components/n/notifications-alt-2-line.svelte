<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf3saabbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf3saabbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-alt-2-line" {...props}></Icon>

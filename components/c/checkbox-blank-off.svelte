<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp1n6kbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp1n6kbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-blank-off" {...props}></Icon>

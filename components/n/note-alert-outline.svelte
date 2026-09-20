<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/did9inf2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="did9inf2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:note-alert-outline" {...props}></Icon>

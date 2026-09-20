<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkb5c9wkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkb5c9wkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:note-outline" {...props}></Icon>

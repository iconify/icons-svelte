<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlg6s6bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlg6s6bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:note-remove" {...props}></Icon>

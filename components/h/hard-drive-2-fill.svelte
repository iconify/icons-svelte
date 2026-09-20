<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t32cmqbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t32cmqbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hard-drive-2-fill" {...props}></Icon>

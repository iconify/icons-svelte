<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujvuz525j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujvuz525j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hard-drive-3-fill" {...props}></Icon>

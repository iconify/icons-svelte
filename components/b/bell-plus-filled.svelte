<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drjg4yr8g.css';
import '../../css/w/w8ad1sbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drjg4yr8g"/><path class="w8ad1sbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-plus-filled" {...props}></Icon>

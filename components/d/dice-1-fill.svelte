<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wurk_8s_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wurk_8s_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-1-fill" {...props}></Icon>

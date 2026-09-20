<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efmcpmb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efmcpmb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ideogram-cjk" {...props}></Icon>

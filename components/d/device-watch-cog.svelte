<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjo0hbcte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjo0hbcte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-cog" {...props}></Icon>

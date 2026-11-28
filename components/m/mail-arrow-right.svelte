<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgpam7bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgpam7bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-arrow-right" {...props}></Icon>

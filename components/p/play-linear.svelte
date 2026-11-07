<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhpn52zsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhpn52zsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-linear" {...props}></Icon>

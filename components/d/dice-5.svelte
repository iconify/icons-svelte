<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vozuasbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vozuasbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-5" {...props}></Icon>

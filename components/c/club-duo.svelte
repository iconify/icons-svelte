<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/digwz38ld.css';
import '../../css/n/nqbz-5bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="digwz38ld secondary"/><path class="nqbz-5bri primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:club-duo" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya0lp56gz.css';
import '../../css/c/ch8mp5-hu.css';
import '../../css/s/sopvr-3ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya0lp56gz"/><path class="ch8mp5-hu"/><path class="sopvr-3ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:akt" {...props}></Icon>

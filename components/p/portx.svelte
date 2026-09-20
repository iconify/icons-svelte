<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmtz-erdo.css';
import '../../css/z/z9hdrkb6h.css';
import '../../css/v/vzqbsgpvh.css';
import '../../css/e/e23x2926m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmtz-erdo"/><path clip-rule="evenodd" class="z9hdrkb6h"/><path class="vzqbsgpvh"/><path clip-rule="evenodd" class="e23x2926m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:portx" {...props}></Icon>

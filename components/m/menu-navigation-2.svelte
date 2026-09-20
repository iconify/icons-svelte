<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1sveoo-n.css';
import '../../css/e/eqoj_abpk.css';
import '../../css/r/r7kgrqbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1sveoo-n"/><path class="eqoj_abpk"/><path class="r7kgrqbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:menu-navigation-2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvm1ofmlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvm1ofmlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:game-2-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgb1ac0gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgb1ac0gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up-right-square-solid" {...props}></Icon>

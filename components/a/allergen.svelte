<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnk5g35xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnk5g35xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:allergen" {...props}></Icon>

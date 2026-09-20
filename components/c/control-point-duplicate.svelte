<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0g6fqbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0g6fqbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:control-point-duplicate" {...props}></Icon>

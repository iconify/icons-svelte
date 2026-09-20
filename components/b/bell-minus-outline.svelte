<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-ohpqbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ohpqbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-minus-outline" {...props}></Icon>

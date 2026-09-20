<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbxakcdnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbxakcdnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-remove-outline" {...props}></Icon>

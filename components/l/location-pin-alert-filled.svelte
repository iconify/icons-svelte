<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etj1eqbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etj1eqbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:location-pin-alert-filled" {...props}></Icon>

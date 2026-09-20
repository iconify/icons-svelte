<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqbyjpvso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqbyjpvso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-container-optimized-os" {...props}></Icon>

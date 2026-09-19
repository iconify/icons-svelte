<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uryce_auj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uryce_auj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:map-location" {...props}></Icon>

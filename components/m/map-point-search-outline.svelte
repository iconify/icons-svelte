<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr_qtkblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr_qtkblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-search-outline" {...props}></Icon>

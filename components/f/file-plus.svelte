<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr9736bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr9736bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-plus" {...props}></Icon>

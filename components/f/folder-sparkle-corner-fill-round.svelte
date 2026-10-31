<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od5n_tliw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od5n_tliw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-sparkle-corner-fill-round" {...props}></Icon>

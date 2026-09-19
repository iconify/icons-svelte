<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gse3s6bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gse3s6bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-adore-alt" {...props}></Icon>

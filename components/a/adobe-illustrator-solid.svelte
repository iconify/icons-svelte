<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw3rumbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw3rumbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:adobe-illustrator-solid" {...props}></Icon>

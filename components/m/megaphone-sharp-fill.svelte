<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij6qmgb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ij6qmgb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:megaphone-sharp-fill" {...props}></Icon>

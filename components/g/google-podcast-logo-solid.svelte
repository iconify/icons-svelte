<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v09uzrn2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v09uzrn2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-podcast-logo-solid" {...props}></Icon>

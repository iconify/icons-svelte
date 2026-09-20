<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlcn8qbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlcn8qbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-shopping-logo-solid" {...props}></Icon>

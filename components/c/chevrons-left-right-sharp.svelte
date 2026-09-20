<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds9laxbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds9laxbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-left-right-sharp" {...props}></Icon>

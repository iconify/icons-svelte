<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x65263l8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x65263l8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:feathub-logo" {...props}></Icon>

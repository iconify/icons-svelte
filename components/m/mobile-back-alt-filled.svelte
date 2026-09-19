<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbhnw7wcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhnw7wcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-back-alt-filled" {...props}></Icon>

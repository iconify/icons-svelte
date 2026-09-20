<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uixl3td8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uixl3td8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:daimler" {...props}></Icon>

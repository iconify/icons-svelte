<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gffp2tb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gffp2tb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lungs" {...props}></Icon>

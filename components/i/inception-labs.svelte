<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijn9g66do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijn9g66do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:inception-labs" {...props}></Icon>

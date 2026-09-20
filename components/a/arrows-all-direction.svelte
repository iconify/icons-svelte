<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rerjc9b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rerjc9b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrows-all-direction" {...props}></Icon>

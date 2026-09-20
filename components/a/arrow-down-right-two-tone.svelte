<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhvv3ymup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhvv3ymup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-right-two-tone" {...props}></Icon>

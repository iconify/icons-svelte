<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iia-u33yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iia-u33yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:figma-broken" {...props}></Icon>

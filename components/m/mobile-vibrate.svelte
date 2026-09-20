<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvvrtzbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvvrtzbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mobile-vibrate" {...props}></Icon>

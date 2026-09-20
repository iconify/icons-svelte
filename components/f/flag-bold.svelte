<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itn0mccsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itn0mccsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sml5s9xuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sml5s9xuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrows-up-down-expressive" {...props}></Icon>

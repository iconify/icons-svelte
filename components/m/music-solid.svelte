<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu40tbc2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu40tbc2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:music-solid" {...props}></Icon>

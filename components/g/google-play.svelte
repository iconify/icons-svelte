<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuqfn8y1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuqfn8y1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:google-play" {...props}></Icon>

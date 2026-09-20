<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw-px0b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw-px0b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pterodactyl" {...props}></Icon>

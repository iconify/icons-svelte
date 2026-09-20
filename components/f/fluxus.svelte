<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijw6f5b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijw6f5b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fluxus" {...props}></Icon>

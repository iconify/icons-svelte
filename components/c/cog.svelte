<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyixq8p0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyixq8p0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cog" {...props}></Icon>

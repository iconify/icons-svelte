<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6icq5pff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6icq5pff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:cog" {...props}></Icon>

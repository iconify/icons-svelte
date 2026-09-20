<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mods8hi-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mods8hi-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:laptop-sharp-fill" {...props}></Icon>

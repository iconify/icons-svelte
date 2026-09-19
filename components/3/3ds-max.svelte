<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi8ylqbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":502};
const content = `<path class="bi8ylqbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:3ds-max" {...props}></Icon>

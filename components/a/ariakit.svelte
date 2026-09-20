<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm0-mtg3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm0-mtg3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ariakit" {...props}></Icon>

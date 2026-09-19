<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hojbiib5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hojbiib5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:plex" {...props}></Icon>

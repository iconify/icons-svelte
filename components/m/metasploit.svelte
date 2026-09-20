<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d339reb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d339reb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:metasploit" {...props}></Icon>

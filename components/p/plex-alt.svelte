<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c691nbcro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c691nbcro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:plex-alt" {...props}></Icon>

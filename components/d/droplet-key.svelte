<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu3v3lbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu3v3lbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-key" {...props}></Icon>

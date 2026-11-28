<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-32uzi1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-32uzi1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:person-plus" {...props}></Icon>

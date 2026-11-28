<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd9pz999j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd9pz999j primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:person-standing-duotone" {...props}></Icon>

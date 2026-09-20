<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shr813boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shr813boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiobookshelf-light" {...props}></Icon>

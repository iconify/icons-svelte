<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz238-fks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz238-fks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiobookshelf-dark" {...props}></Icon>

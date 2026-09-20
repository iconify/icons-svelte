<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq99g-23z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq99g-23z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:featured-playlist-line" {...props}></Icon>

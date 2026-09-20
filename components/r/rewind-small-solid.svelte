<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loilifxwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="loilifxwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rewind-small-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-y0upb3c.css';
import '../../css/h/hmwkp1a3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b-y0upb3c"/><path clip-rule="evenodd" class="hmwkp1a3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:instagram-solid" {...props}></Icon>

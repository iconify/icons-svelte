<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apugdvb-c.css';
import '../../css/p/pt1w2bihr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="apugdvb-c"/><path clip-rule="evenodd" class="pt1w2bihr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:image-alt-solid" {...props}></Icon>

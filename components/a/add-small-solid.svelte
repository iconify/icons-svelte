<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evfk3vb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="evfk3vb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:add-small-solid" {...props}></Icon>

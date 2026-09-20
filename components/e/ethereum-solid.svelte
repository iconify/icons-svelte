<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le4i3-b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="le4i3-b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ethereum-solid" {...props}></Icon>

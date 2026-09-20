<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw2t20ski.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rw2t20ski"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pause-circle-solid" {...props}></Icon>

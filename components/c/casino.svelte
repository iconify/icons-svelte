<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7kzzzk4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k7kzzzk4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:casino" {...props}></Icon>

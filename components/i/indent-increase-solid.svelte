<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijwmx3hsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ijwmx3hsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:indent-increase-solid" {...props}></Icon>

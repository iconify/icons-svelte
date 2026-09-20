<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmvobsz7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pmvobsz7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pause-solid" {...props}></Icon>

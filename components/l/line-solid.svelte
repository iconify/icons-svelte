<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiycpfkrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iiycpfkrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:line-solid" {...props}></Icon>

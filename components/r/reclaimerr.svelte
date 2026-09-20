<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz0_h5o9w.css';
import '../../css/a/adkjrqbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jz0_h5o9w"/><path class="adkjrqbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reclaimerr" {...props}></Icon>

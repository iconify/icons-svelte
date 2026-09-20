<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm28nkbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm28nkbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:healthchecks-dark" {...props}></Icon>

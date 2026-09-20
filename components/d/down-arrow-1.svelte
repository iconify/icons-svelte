<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eahow9bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eahow9bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:down-arrow-1" {...props}></Icon>

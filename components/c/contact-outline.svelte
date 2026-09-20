<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s380qsb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s380qsb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:contact-outline" {...props}></Icon>

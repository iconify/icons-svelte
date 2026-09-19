<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6n_p9b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="w6n_p9b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-tears" {...props}></Icon>

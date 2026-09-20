<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0nw_p33t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0nw_p33t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:clickup" {...props}></Icon>

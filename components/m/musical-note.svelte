<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5u5w1b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5u5w1b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:musical-note" {...props}></Icon>

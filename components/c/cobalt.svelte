<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn7nyeb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn7nyeb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cobalt" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy3hx35ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy3hx35ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-minus" {...props}></Icon>

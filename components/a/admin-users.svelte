<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it_flsb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="it_flsb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-users" {...props}></Icon>

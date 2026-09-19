<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujh6q_bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujh6q_bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:person-circle-sharp" {...props}></Icon>

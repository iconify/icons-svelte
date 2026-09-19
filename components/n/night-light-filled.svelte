<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq300m9xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq300m9xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:night-light-filled" {...props}></Icon>

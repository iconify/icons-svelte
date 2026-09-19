<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwkrqqb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwkrqqb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-05" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlzij9bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlzij9bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hammer" {...props}></Icon>

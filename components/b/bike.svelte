<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p85_17h2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p85_17h2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bike" {...props}></Icon>

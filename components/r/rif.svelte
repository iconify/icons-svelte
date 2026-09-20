<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq9_55bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq9_55bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rif" {...props}></Icon>

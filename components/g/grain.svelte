<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pweakh6eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pweakh6eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grain" {...props}></Icon>

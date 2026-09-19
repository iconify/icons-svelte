<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyi3rac9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyi3rac9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:filter-off-outline" {...props}></Icon>

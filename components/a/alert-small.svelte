<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvol2gbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvol2gbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-small" {...props}></Icon>

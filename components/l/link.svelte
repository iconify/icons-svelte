<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4u87obbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4u87obbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:link" {...props}></Icon>

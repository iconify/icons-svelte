<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u48rs9bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="u48rs9bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:brush-2" {...props}></Icon>

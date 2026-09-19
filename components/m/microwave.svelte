<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tycoh_b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":832};
const content = `<path class="tycoh_b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:microwave" {...props}></Icon>

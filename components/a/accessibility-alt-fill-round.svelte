<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj3nw3btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3nw3btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:accessibility-alt-fill-round" {...props}></Icon>

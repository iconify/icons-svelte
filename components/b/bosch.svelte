<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kief4lrfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kief4lrfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bosch" {...props}></Icon>

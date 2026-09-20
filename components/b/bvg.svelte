<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxg7xccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxg7xccaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bvg" {...props}></Icon>

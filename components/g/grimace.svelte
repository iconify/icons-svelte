<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auxx8in_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="auxx8in_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grimace" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbgjb1_vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fbgjb1_vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:caligraphy" {...props}></Icon>

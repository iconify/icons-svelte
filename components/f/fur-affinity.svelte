<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btz72t84e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btz72t84e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fur-affinity" {...props}></Icon>

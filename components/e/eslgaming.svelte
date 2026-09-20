<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1x6qhb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1x6qhb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eslgaming" {...props}></Icon>

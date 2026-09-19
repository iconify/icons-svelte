<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3zgc2n5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="n3zgc2n5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:lightnings" {...props}></Icon>

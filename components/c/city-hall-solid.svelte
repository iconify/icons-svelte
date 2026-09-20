<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1w3bn26c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r1w3bn26c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:city-hall-solid" {...props}></Icon>

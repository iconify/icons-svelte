<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcc368ecc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":712.96,"height":712.96,"left":-346.211,"top":-706.48};
const content = `<path class="hcc368ecc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pocket-id-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c58_3zblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":258};
const content = `<path class="c58_3zblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mongodb-light" {...props}></Icon>

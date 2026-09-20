<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyu8dvsvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="hyu8dvsvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ferry-11" {...props}></Icon>

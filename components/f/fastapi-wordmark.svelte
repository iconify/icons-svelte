<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw8ctlbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aw8ctlbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:fastapi-wordmark" {...props}></Icon>

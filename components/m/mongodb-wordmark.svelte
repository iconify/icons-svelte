<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7e5xobtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="d7e5xobtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:mongodb-wordmark" {...props}></Icon>

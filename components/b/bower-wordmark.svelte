<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h16-qvbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="h16-qvbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bower-wordmark" {...props}></Icon>

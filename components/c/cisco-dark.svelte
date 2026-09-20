<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua73idyup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":52,"height":28};
const content = `<path clip-rule="evenodd" class="ua73idyup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cisco-dark" {...props}></Icon>

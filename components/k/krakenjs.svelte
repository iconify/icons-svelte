<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zowtftbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="zowtftbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:krakenjs" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leae0xb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":184.84,"height":59.76};
const content = `<path class="leae0xb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:powerade" {...props}></Icon>

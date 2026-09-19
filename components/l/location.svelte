<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcny89buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":586,"height":1000};
const content = `<path class="dcny89buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:location" {...props}></Icon>

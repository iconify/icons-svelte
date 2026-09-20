<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1l5dhiww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v1l5dhiww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-key" {...props}></Icon>

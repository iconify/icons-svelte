<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h15ryn7dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h15ryn7dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pound-solid" {...props}></Icon>

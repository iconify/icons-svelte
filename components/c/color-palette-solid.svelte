<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mitljhbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="mitljhbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:color-palette-solid" {...props}></Icon>

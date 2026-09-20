<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff9amtfnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ff9amtfnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pin-alt-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n54nlf2gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n54nlf2gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:loader-solid" {...props}></Icon>

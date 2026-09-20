<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jykl4mcwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jykl4mcwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:eye-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzt0lm2ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pzt0lm2ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:discount-solid" {...props}></Icon>

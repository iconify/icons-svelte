<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kydskppsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kydskppsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:link-solid" {...props}></Icon>

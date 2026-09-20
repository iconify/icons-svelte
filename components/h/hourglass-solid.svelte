<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb7wp_mkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="lb7wp_mkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hourglass-solid" {...props}></Icon>

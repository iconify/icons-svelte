<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwb5pczfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uwb5pczfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:battery-half" {...props}></Icon>

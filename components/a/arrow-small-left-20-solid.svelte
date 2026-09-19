<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsn_v_jiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jsn_v_jiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-left-20-solid" {...props}></Icon>

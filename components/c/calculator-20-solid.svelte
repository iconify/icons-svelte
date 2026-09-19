<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqx-rabmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xqx-rabmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calculator-20-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn96lgbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dn96lgbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-left-20-solid" {...props}></Icon>

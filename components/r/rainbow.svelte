<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1lvcxb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k1lvcxb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rainbow" {...props}></Icon>

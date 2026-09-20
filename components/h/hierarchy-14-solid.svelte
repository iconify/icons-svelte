<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjtwp-bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kjtwp-bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-14-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1wpx7blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t1wpx7blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:circle-clock-solid" {...props}></Icon>

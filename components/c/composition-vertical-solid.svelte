<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezuox2bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ezuox2bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:composition-vertical-solid" {...props}></Icon>

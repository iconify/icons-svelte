<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdmx7eosl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wdmx7eosl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:rectangle-one" {...props}></Icon>

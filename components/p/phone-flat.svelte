<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hege8bcxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hege8bcxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:phone-flat" {...props}></Icon>

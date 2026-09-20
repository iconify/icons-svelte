<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wje8iccmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wje8iccmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:arrow-turn-down-large-flat" {...props}></Icon>

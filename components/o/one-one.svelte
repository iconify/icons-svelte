<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etb614apb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="etb614apb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:one-one" {...props}></Icon>

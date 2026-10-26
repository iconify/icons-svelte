<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amaq5lbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="amaq5lbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:chevron-left" {...props}></Icon>

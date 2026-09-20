<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us8ih0gnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="us8ih0gnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cloud-off" {...props}></Icon>

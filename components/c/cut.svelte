<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmg620o6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vmg620o6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cut" {...props}></Icon>

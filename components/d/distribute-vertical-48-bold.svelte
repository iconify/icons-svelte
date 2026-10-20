<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke8gj0i4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ke8gj0i4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:distribute-vertical-48-bold" {...props}></Icon>

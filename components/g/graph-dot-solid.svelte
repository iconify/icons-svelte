<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur-7fqmse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ur-7fqmse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:graph-dot-solid" {...props}></Icon>

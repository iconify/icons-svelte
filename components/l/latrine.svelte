<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m006cx35p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":48};
const content = `<path class="m006cx35p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:latrine" {...props}></Icon>

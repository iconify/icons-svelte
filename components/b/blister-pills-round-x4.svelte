<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmwv8bbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pmwv8bbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-round-x4" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnsd8h9em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dnsd8h9em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:pet-paw-flat" {...props}></Icon>

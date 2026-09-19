<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smq2_2b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="smq2_2b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:generic-sorting-desc" {...props}></Icon>

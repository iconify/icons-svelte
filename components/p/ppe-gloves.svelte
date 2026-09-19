<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0d5r2voh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f0d5r2voh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-gloves" {...props}></Icon>

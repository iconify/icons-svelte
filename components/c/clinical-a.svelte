<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skhz5ybrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="skhz5ybrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:clinical-a" {...props}></Icon>

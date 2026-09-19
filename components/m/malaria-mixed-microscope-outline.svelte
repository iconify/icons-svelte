<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivczqoblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ivczqoblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:malaria-mixed-microscope-outline" {...props}></Icon>

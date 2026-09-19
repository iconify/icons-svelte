<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5dz2tbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z5dz2tbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:malaria-pv-microscope-outline" {...props}></Icon>

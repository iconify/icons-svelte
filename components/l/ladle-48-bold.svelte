<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oshhv4dvv.css';
import '../../css/o/ohv239ijk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oshhv4dvv"/><path class="ohv239ijk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladle-48-bold" {...props}></Icon>

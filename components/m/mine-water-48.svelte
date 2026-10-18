<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7ezmybgf.css';
import '../../css/e/elzyb5xmp.css';
import '../../css/o/ovlh7zbng.css';
import '../../css/n/nqumikboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r7ezmybgf"/><path class="elzyb5xmp"/><path class="ovlh7zbng"/><path class="nqumikboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-water-48" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqt06ac5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cqt06ac5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:microscope-observation-sciene-solid" {...props}></Icon>

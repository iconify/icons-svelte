<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5nn_nvzj.css';
import '../../css/y/yrrvfsjve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c5nn_nvzj"/><path class="yrrvfsjve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-crack-48-bold" {...props}></Icon>

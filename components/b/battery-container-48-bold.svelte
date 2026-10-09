<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jukv1_4-a.css';
import '../../css/x/xoemm8bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jukv1_4-a"/><path class="xoemm8bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-container-48-bold" {...props}></Icon>

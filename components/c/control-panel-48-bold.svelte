<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzpmmxj6m.css';
import '../../css/j/jrayg3xau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jzpmmxj6m"/><path class="jrayg3xau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-panel-48-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqdkyobsr.css';
import '../../css/p/pw-txxw1n.css';
import '../../css/s/su-rh8qhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqdkyobsr"/><path class="pw-txxw1n"/><path class="su-rh8qhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:assembly-line-48" {...props}></Icon>

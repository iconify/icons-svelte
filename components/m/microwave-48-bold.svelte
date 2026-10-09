<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/defz0cbcm.css';
import '../../css/o/oxmy0inzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="defz0cbcm"/><path class="oxmy0inzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microwave-48-bold" {...props}></Icon>

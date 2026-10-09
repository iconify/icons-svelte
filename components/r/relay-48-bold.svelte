<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4j2f0pva.css';
import '../../css/w/wegshrb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k4j2f0pva"/><path class="wegshrb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:relay-48-bold" {...props}></Icon>

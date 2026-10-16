<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgiazbbrf.css';
import '../../css/s/sf7om5bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qgiazbbrf"/><path class="sf7om5bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-open-20" {...props}></Icon>

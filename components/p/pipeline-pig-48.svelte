<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgga-fb4g.css';
import '../../css/s/sw35zxvtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jgga-fb4g"/><path class="sw35zxvtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-pig-48" {...props}></Icon>

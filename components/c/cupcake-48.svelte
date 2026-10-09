<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_lg07b5j.css';
import '../../css/m/mq-hp4bft.css';
import '../../css/j/jw7uenmxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i_lg07b5j"/><path class="mq-hp4bft"/><path class="jw7uenmxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cupcake-48" {...props}></Icon>

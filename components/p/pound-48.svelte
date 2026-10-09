<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncqap6kqt.css';
import '../../css/w/w4cmqe7qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ncqap6kqt"/><path class="w4cmqe7qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pound-48" {...props}></Icon>

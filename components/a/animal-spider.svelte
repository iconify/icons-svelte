<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siikb1s6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="siikb1s6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:animal-spider" {...props}></Icon>

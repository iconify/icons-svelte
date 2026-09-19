<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq2h2if7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fq2h2if7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:level-four-title" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgi-m3bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jgi-m3bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-text-left" {...props}></Icon>

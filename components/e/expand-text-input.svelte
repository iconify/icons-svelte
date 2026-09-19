<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf-ij7u5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vf-ij7u5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:expand-text-input" {...props}></Icon>

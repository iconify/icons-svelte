<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvzf_gblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gvzf_gblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:magnet" {...props}></Icon>

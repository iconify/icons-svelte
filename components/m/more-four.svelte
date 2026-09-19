<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu3p7dkjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cu3p7dkjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:more-four" {...props}></Icon>

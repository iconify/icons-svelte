<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kext3dbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kext3dbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cable-car" {...props}></Icon>

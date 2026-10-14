<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij8caccud.css';
import '../../css/p/p05vswb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8caccud"/><path class="p05vswb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codescan-24" {...props}></Icon>

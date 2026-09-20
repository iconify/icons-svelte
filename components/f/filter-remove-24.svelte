<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prm7xpbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prm7xpbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:filter-remove-24" {...props}></Icon>

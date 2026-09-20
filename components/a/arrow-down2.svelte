<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pik0u_bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pik0u_bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa3e_ihor.css';
import '../../css/s/ss1-wab0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa3e_ihor"/><path class="ss1-wab0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyboard" {...props}></Icon>

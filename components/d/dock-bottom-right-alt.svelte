<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxxuevbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxxuevbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-right-alt" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmimpobif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmimpobif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menu-left-filled" {...props}></Icon>

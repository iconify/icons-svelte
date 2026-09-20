<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uerla3dof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uerla3dof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:archive-2-fill" {...props}></Icon>

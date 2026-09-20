<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3dkirz7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dkirz7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-specialty-nose-bold" {...props}></Icon>

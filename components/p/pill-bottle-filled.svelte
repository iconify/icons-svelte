<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfcrsdfef.css';
import '../../css/o/ot8dm5bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfcrsdfef"/><path class="ot8dm5bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pill-bottle-filled" {...props}></Icon>

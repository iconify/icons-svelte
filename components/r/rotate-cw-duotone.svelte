<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crzvukbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crzvukbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rotate-cw-duotone" {...props}></Icon>

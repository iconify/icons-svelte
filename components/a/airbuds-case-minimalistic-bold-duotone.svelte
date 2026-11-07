<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z58cvdbyi.css';
import '../../css/z/zy_e48yuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z58cvdbyi"/><path class="zy_e48yuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-case-minimalistic-bold-duotone" {...props}></Icon>

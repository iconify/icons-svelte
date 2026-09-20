<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkl3x0lvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkl3x0lvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:heroui" {...props}></Icon>

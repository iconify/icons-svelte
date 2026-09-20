<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnuscxboo.css';
import '../../css/o/o44bltb0y.css';
import '../../css/x/xuokrglbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="fnuscxboo"/><path class="o44bltb0y"/><path clip-rule="evenodd" class="xuokrglbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:globus-bold-duotone" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm5tes3gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm5tes3gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dumbbell-plus" {...props}></Icon>

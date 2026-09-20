<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebs3ndmsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebs3ndmsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:ironing-board" {...props}></Icon>

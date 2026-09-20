<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9e95ubyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9e95ubyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:iron" {...props}></Icon>

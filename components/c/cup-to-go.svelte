<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycwxoq74a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycwxoq74a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cup-to-go" {...props}></Icon>

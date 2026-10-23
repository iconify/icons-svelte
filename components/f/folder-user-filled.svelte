<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5at6trmc.css';
import '../../css/i/i669q6bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5at6trmc"/><path class="i669q6bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-user-filled" {...props}></Icon>

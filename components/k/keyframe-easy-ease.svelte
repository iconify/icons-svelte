<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1vqubil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1vqubil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-easy-ease" {...props}></Icon>

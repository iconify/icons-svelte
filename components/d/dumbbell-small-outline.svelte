<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghj_vqn2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ghj_vqn2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-small-outline" {...props}></Icon>

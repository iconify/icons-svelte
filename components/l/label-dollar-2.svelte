<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utawi2b_n.css';
import '../../css/m/mx3dnrxyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utawi2b_n"/><path clip-rule="evenodd" class="mx3dnrxyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:label-dollar-2" {...props}></Icon>

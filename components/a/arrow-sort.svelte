<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0sg_1bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0sg_1bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-sort" {...props}></Icon>

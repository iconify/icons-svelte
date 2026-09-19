<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek-nq_bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek-nq_bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:headphones-outline" {...props}></Icon>

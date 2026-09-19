<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl25s0bgy.css';
import '../../css/r/r-n6f1bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl25s0bgy"/><path class="r-n6f1bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-right-square-filled" {...props}></Icon>

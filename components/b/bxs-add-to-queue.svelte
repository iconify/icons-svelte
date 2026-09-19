<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9y7lbbej.css';
import '../../css/u/u45py-vnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9y7lbbej"/><path class="u45py-vnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-add-to-queue" {...props}></Icon>

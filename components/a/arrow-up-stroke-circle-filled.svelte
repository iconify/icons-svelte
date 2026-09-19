<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7kwzsb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7kwzsb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-stroke-circle-filled" {...props}></Icon>

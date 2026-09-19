<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frbvlobom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frbvlobom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-right-circle-filled" {...props}></Icon>

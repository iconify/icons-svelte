<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro145-ule.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro145-ule"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:component-filled" {...props}></Icon>

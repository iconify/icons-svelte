<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em-bjibae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em-bjibae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-minus-filled" {...props}></Icon>

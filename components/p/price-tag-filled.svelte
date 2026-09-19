<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeak2jbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeak2jbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:price-tag-filled" {...props}></Icon>

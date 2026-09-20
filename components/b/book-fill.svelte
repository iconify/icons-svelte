<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emplo6mir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emplo6mir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:book-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlt74o7ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlt74o7ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-down-fill" {...props}></Icon>

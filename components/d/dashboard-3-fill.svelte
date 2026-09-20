<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uei7otwae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uei7otwae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-3-fill" {...props}></Icon>

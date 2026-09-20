<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxn0p0b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxn0p0b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-down-b-fill" {...props}></Icon>

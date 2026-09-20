<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfiwtzbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfiwtzbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-right-circle-fill" {...props}></Icon>

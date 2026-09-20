<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_x5bub4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_x5bub4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:pinterest" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtpdo_-qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="qtpdo_-qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:menu-meatballs-2" {...props}></Icon>

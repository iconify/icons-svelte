<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-n7-wbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-n7-wbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-up-square-fill" {...props}></Icon>

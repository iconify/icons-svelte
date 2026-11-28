<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5rzl_u5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5rzl_u5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:coins-stack-solid" {...props}></Icon>

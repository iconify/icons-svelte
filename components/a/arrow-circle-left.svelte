<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz4u5db2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz4u5db2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-circle-left" {...props}></Icon>

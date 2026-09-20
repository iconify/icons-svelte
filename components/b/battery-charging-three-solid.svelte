<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ea00rjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ea00rjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-charging-three-solid" {...props}></Icon>

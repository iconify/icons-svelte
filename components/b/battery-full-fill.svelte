<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc-34jbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc-34jbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:battery-full-fill" {...props}></Icon>

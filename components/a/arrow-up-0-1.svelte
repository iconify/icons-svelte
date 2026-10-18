<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_21rcbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_21rcbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-0-1" {...props}></Icon>

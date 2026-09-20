<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngz-g_2fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngz-g_2fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fanfou" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkk3whelo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkk3whelo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:compass" {...props}></Icon>

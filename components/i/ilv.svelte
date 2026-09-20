<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yakzyezhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yakzyezhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ilv" {...props}></Icon>

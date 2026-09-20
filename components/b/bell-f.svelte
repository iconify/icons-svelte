<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfhu18_2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="dfhu18_2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bell-f" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljas3ofjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljas3ofjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bug-fill" {...props}></Icon>

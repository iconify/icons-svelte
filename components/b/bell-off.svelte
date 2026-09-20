<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn-xy7bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn-xy7bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-off" {...props}></Icon>

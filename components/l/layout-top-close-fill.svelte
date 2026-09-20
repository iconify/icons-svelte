<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo9n361qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo9n361qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-top-close-fill" {...props}></Icon>

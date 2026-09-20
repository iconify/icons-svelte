<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnncbwbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnncbwbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drumsticks-24" {...props}></Icon>

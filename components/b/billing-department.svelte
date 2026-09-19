<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nprx-pcld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nprx-pcld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:billing-department" {...props}></Icon>

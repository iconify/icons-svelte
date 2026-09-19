<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c63ibibyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c63ibibyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:folder-arrow-right-outline" {...props}></Icon>

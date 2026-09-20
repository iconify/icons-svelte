<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k12150_0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k12150_0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:link-2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oly8rvbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="oly8rvbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:box-f" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_b9ttbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-4.5};
const content = `<path class="u_b9ttbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:plus" {...props}></Icon>

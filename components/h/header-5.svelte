<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llnvy_sqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-6.5};
const content = `<path class="llnvy_sqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:header-5" {...props}></Icon>

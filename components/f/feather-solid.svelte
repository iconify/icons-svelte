<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hklh74bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hklh74bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:feather-solid" {...props}></Icon>

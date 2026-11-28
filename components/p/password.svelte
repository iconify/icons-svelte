<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wyeomct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-wyeomct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:password" {...props}></Icon>

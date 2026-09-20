<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujesk2bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujesk2bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-fill" {...props}></Icon>

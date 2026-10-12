<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1y6bsbqe.css';
import '../../css/a/aldux5bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n1y6bsbqe"/><path class="aldux5bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-mask-20" {...props}></Icon>

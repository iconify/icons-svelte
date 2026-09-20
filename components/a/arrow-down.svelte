<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khz2yzbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-4.5};
const content = `<path class="khz2yzbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-down" {...props}></Icon>

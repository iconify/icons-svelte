<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4hy-p3tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4hy-p3tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:huawei" {...props}></Icon>

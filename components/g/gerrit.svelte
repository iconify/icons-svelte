<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omgi_ocxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omgi_ocxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gerrit" {...props}></Icon>

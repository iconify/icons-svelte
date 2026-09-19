<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsy7k0alc.css';
import '../../css/z/zt-51hcly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsy7k0alc"/><path class="zt-51hcly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:meteor" {...props}></Icon>

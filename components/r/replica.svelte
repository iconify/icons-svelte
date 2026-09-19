<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck52k8vxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck52k8vxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:replica" {...props}></Icon>

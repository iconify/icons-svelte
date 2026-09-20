<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-g98yz0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="w-g98yz0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cloud-thunder" {...props}></Icon>

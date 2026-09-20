<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-4shmbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="q-4shmbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cloud-snow-f" {...props}></Icon>

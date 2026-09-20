<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwbvoi8sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwbvoi8sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:left-down-duotone" {...props}></Icon>

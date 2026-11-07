<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkj7k3nbl.css';
import '../../css/h/hnfc23bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj7k3nbl"/><path clip-rule="evenodd" class="hnfc23bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:export-bold-duotone" {...props}></Icon>

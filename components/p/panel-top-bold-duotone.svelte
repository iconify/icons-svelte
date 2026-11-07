<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2z1e_f9o.css';
import '../../css/b/br5lnd2bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2z1e_f9o"/><path class="br5lnd2bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-bold-duotone" {...props}></Icon>

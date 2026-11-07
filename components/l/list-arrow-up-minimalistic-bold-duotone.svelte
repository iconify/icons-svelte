<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdarr4bmq.css';
import '../../css/h/hqrr-dbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdarr4bmq"/><path class="hqrr-dbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-up-minimalistic-bold-duotone" {...props}></Icon>

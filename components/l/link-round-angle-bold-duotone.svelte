<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt-_h2mmy.css';
import '../../css/g/ge8axobmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt-_h2mmy"/><path class="ge8axobmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-round-angle-bold-duotone" {...props}></Icon>

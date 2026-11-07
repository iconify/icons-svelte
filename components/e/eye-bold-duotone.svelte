<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noq8vw_6n.css';
import '../../css/k/k7zx50lak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noq8vw_6n"/><path clip-rule="evenodd" class="k7zx50lak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eye-bold-duotone" {...props}></Icon>

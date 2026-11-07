<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz_lgvb5c.css';
import '../../css/a/adl-4zb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz_lgvb5c"/><path class="adl-4zb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-bold-duotone" {...props}></Icon>

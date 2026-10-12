<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_vsq7l3i.css';
import '../../css/u/uai873b4f.css';
import '../../css/s/s_p56dbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="uai873b4f"/><path class="s_p56dbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-plus-filled" {...props}></Icon>

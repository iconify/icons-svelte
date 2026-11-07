<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0a04rwms.css';
import '../../css/v/vlwih1bec.css';
import '../../css/l/lwsxc47kb.css';
import '../../css/k/kkhl62fff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0a04rwms"/><path class="vlwih1bec"/><path class="lwsxc47kb"/><path class="kkhl62fff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:password-minimalistic-input-outline" {...props}></Icon>

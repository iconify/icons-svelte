<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwezt-ini.css';
import '../../css/k/k0vfem02x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fwezt-ini"/><path class="k0vfem02x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:reply-to-message-typing-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfe_wvkpo.css';
import '../../css/t/t3678pb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfe_wvkpo"/><path class="t3678pb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:code-block-solid" {...props}></Icon>

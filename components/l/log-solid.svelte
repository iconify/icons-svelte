<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie_f_acfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ie_f_acfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:log-solid" {...props}></Icon>

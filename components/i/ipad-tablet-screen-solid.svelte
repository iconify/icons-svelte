<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz-zlvl4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mz-zlvl4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ipad-tablet-screen-solid" {...props}></Icon>

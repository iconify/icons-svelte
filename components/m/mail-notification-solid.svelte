<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ectnb4k.css';
import '../../css/t/ti-3o5bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ectnb4k"/><path class="ti-3o5bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-notification-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr2ujbbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr2ujbbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:link-broken-filled" {...props}></Icon>

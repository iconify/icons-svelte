<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wazqkkfbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wazqkkfbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ban-solid" {...props}></Icon>

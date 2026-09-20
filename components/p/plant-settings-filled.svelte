<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ynbhb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a-ynbhb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plant-settings-filled" {...props}></Icon>

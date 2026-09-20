<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3k0dshgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3k0dshgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-multiple-add-outline" {...props}></Icon>

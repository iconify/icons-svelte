<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcz-rc2-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tcz-rc2-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ciphermail-dark" {...props}></Icon>

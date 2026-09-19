<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejpq9_evm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ejpq9_evm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-wink" {...props}></Icon>

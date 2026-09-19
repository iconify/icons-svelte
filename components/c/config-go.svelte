<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m64hpwtxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m64hpwtxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-go" {...props}></Icon>

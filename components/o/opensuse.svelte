<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mybu-2pkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mybu-2pkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse" {...props}></Icon>

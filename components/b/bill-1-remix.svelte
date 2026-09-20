<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyoux5b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kyoux5b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bill-1-remix" {...props}></Icon>

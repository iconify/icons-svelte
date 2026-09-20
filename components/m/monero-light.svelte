<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1kuc2bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1kuc2bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monero-light" {...props}></Icon>

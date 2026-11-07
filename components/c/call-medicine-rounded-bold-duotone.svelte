<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkxo3pbyr.css';
import '../../css/x/x6g9eebag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fkxo3pbyr"/><path class="x6g9eebag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-medicine-rounded-bold-duotone" {...props}></Icon>

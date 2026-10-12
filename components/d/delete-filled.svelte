<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stf1opbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stf1opbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:delete-filled" {...props}></Icon>

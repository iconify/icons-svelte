<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrkgxobnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mrkgxobnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:earth-filled" {...props}></Icon>

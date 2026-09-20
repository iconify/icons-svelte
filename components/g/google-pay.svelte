<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl_v98bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl_v98bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:google-pay" {...props}></Icon>

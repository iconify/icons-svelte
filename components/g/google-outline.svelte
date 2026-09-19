<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdzfnr7gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdzfnr7gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:google-outline" {...props}></Icon>

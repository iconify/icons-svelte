<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp6f-bgms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp6f-bgms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-bulk-round" {...props}></Icon>

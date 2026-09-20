<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swv0urbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swv0urbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brightness-fill" {...props}></Icon>

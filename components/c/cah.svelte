<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu68r3blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu68r3blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cah" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my2u87bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="my2u87bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-vibrate-filled" {...props}></Icon>

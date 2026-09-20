<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcq7sn2qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcq7sn2qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mic2" {...props}></Icon>

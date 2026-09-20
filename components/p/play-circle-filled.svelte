<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvh93qr1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvh93qr1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:play-circle-filled" {...props}></Icon>

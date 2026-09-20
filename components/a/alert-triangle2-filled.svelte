<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exhuzbbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="exhuzbbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alert-triangle2-filled" {...props}></Icon>

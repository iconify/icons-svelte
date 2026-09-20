<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcu5i0bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcu5i0bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dbc" {...props}></Icon>

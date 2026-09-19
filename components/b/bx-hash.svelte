<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw780st6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw780st6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-hash" {...props}></Icon>

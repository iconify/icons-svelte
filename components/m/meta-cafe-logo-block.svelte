<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2lc4yp1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2lc4yp1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:meta-cafe-logo-block" {...props}></Icon>

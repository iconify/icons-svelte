<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb3vq1y9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb3vq1y9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:labex" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn6lwobzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn6lwobzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-read" {...props}></Icon>

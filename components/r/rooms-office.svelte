<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw6oiua1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw6oiua1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-office" {...props}></Icon>

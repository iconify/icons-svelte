<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf_w8fb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf_w8fb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cassette" {...props}></Icon>

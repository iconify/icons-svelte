<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7o8pkuib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7o8pkuib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:asteroid" {...props}></Icon>

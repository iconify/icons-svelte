<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6gstblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd6gstblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:obot" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c77347-xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c77347-xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reply2-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjhclzbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yjhclzbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ev-charge-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4-ziybhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4-ziybhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart3-filled" {...props}></Icon>

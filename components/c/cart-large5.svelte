<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf-01p6qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf-01p6qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart-large5" {...props}></Icon>

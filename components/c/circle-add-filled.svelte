<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbc-skb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xbc-skb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-add-filled" {...props}></Icon>

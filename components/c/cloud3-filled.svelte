<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnfj03b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnfj03b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud3-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbw2iscqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbw2iscqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:group4-filled" {...props}></Icon>

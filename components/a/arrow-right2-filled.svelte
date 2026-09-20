<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idsrdcruo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idsrdcruo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right2-filled" {...props}></Icon>

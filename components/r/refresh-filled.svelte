<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxuyjmbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxuyjmbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh-filled" {...props}></Icon>

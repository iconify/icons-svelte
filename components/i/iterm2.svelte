<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tih5mtbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tih5mtbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iterm2" {...props}></Icon>

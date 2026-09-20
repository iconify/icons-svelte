<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8_l82buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8_l82buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag3" {...props}></Icon>

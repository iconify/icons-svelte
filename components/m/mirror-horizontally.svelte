<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txzvtkb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txzvtkb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mirror-horizontally" {...props}></Icon>

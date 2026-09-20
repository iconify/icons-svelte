<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl4iseoju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl4iseoju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:check-double" {...props}></Icon>

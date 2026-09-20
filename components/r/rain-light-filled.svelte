<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boc6a8b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boc6a8b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rain-light-filled" {...props}></Icon>

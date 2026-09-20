<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-zu4_btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-zu4_btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangle-vertical" {...props}></Icon>

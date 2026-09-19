<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkz_ggbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkz_ggbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:clipboard" {...props}></Icon>

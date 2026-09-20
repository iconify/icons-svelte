<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiz_subtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tiz_subtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-bold" {...props}></Icon>

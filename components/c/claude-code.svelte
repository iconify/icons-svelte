<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d51wc_brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d51wc_brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:claude-code" {...props}></Icon>

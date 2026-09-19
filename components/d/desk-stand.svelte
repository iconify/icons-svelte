<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5m5mqbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5m5mqbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:desk-stand" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agnqmmhmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agnqmmhmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-cny-line" {...props}></Icon>

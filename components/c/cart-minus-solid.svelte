<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4p_vim0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4p_vim0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cart-minus-solid" {...props}></Icon>

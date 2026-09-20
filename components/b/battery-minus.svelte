<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzmbzpyvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzmbzpyvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-minus" {...props}></Icon>

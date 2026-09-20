<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da4_wc1jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da4_wc1jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-eleven-solid" {...props}></Icon>

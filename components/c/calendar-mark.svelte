<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoo7dmbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eoo7dmbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-mark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vowtz-pcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vowtz-pcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:calendar-plus" {...props}></Icon>

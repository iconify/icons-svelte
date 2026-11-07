<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvvgatbpq.css';
import '../../css/x/xgwd3dwqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvvgatbpq"/><path class="xgwd3dwqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-outline" {...props}></Icon>

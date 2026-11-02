<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw535xgbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw535xgbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-8-line" {...props}></Icon>

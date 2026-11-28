<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfz9u0b1c.css';
import '../../css/a/ao__mmbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfz9u0b1c secondary"/><path class="ao__mmbtc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-loop-limit-duo" {...props}></Icon>

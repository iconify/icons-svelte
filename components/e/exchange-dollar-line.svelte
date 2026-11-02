<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq9mfi5qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq9mfi5qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-dollar-line" {...props}></Icon>

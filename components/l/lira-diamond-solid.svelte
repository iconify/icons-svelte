<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1gqv4b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1gqv4b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lira-diamond-solid" {...props}></Icon>

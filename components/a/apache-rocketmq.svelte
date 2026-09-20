<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5wyw4dnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5wyw4dnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-rocketmq" {...props}></Icon>

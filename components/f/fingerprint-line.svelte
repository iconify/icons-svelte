<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx0mq7gqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx0mq7gqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fingerprint-line" {...props}></Icon>

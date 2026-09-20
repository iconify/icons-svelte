<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq9sayxnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq9sayxnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:a-arrow-up" {...props}></Icon>

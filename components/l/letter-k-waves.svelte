<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9dq5q5ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9dq5q5ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-waves" {...props}></Icon>

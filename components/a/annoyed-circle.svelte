<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7hw3pbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7hw3pbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:annoyed-circle" {...props}></Icon>

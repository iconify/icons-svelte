<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/issvxhbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="issvxhbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pendle" {...props}></Icon>

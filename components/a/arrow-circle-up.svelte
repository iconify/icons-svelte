<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yurwaccmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yurwaccmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:arrow-circle-up" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypzsvm3is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypzsvm3is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:radio-x" {...props}></Icon>

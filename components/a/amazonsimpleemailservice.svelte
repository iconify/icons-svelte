<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjsq2obcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjsq2obcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonsimpleemailservice" {...props}></Icon>

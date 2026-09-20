<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiu4072ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiu4072ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:link-tiny" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q406r4l9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q406r4l9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bed" {...props}></Icon>

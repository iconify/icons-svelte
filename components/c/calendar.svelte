<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm7bg7waf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm7bg7waf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar" {...props}></Icon>

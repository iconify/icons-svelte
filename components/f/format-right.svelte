<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hve_623ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hve_623ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-right" {...props}></Icon>

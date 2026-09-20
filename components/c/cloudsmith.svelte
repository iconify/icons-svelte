<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toob-9b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toob-9b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cloudsmith" {...props}></Icon>

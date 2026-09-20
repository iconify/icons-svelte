<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co6v_pfaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co6v_pfaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jbl" {...props}></Icon>

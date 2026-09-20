<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cze0zhbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cze0zhbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:platformdotsh" {...props}></Icon>

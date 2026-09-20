<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx6820b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx6820b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:border-right" {...props}></Icon>

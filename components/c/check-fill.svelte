<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsl6db1of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsl6db1of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-fill" {...props}></Icon>

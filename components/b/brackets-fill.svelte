<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufqns12ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufqns12ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brackets-fill" {...props}></Icon>

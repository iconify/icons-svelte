<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt4uvwnpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt4uvwnpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-ax" {...props}></Icon>

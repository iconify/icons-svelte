<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1n53nssr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1n53nssr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:chandelier" {...props}></Icon>

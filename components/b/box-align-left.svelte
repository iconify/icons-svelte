<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6or3jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6or3jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-left" {...props}></Icon>

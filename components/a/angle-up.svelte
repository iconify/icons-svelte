<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4csfvb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4csfvb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:angle-up" {...props}></Icon>
